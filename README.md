# Server Metrics 2026-03-13 18:34:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 131759.8 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4211492
telemt_connections_bad_total 37626
telemt_handshake_timeouts_total 102451
telemt_upstream_connect_attempt_total 27829
telemt_upstream_connect_success_total 27646
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 27829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 5787
telemt_me_reconnect_attempts_total 28830
telemt_me_reconnect_success_total 18723
telemt_me_reader_eof_total 20106
telemt_me_idle_close_by_peer_total 20105
telemt_me_route_drop_no_conn_total 1576060
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3849271
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15054
telemt_desync_full_logged_total 4005
telemt_desync_suppressed_total 11049
telemt_desync_frames_bucket_total{bucket="1_2"} 3746
telemt_desync_frames_bucket_total{bucket="3_10"} 5725
telemt_desync_frames_bucket_total{bucket="gt_10"} 5583
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19303
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18710
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 3851443
telemt_user_connections_current{user="hello"} 1532
telemt_user_octets_from_client{user="hello"} 53919626732 (50.22 GB)
telemt_user_octets_to_client{user="hello"} 1204931505065 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31423.8 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464064
telemt_connections_bad_total 36172
telemt_handshake_timeouts_total 10762
telemt_upstream_connect_attempt_total 8882
telemt_upstream_connect_success_total 8699
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 8882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 1614
telemt_me_reconnect_attempts_total 9096
telemt_me_reconnect_success_total 5695
telemt_me_reader_eof_total 6011
telemt_me_idle_close_by_peer_total 6010
telemt_me_route_drop_no_conn_total 174633
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403834
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1420
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 1047
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5878
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5687
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 405171
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 4189188943 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 125092605188 (116.50 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 161380.6 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3077971
telemt_connections_bad_total 28928
telemt_handshake_timeouts_total 206386
telemt_upstream_connect_attempt_total 35916
telemt_upstream_connect_success_total 35906
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3515
telemt_me_reconnect_attempts_total 30090
telemt_me_reconnect_success_total 27535
telemt_me_reader_eof_total 29199
telemt_me_idle_close_by_peer_total 29198
telemt_me_route_drop_no_conn_total 1052703
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2545902
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8560
telemt_desync_full_logged_total 2840
telemt_desync_suppressed_total 5720
telemt_desync_frames_bucket_total{bucket="1_2"} 1386
telemt_desync_frames_bucket_total{bucket="3_10"} 3130
telemt_desync_frames_bucket_total{bucket="gt_10"} 4044
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 27857
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27494
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 2545205
telemt_user_connections_current{user="hello"} 912
telemt_user_octets_from_client{user="hello"} 42010215188 (39.13 GB)
telemt_user_octets_to_client{user="hello"} 893885203905 (832.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 161380.9 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1979685
telemt_connections_bad_total 20151
telemt_handshake_timeouts_total 181975
telemt_upstream_connect_attempt_total 49828
telemt_upstream_connect_success_total 47482
telemt_upstream_connect_fail_total 2209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49554
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2208
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11973
telemt_me_reconnect_attempts_total 42572
telemt_me_reconnect_success_total 33586
telemt_me_reader_eof_total 36065
telemt_me_idle_close_by_peer_total 36058
telemt_me_route_drop_no_conn_total 704862
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1634294
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3330
telemt_desync_full_logged_total 1079
telemt_desync_suppressed_total 2251
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1355
telemt_desync_frames_bucket_total{bucket="gt_10"} 1068
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 34140
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33562
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 1638989
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 25224048329 (23.49 GB)
telemt_user_octets_to_client{user="hello"} 618693850030 (576.20 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30816.4 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503643
telemt_connections_bad_total 4724
telemt_handshake_timeouts_total 5114
telemt_upstream_connect_attempt_total 6832
telemt_upstream_connect_success_total 6611
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 6832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 877
telemt_me_reconnect_attempts_total 23243
telemt_me_reconnect_success_total 5035
telemt_me_reader_eof_total 5701
telemt_me_idle_close_by_peer_total 5701
telemt_me_route_drop_no_conn_total 191295
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471757
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1368
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 932
telemt_desync_frames_bucket_total{bucket="1_2"} 429
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 401
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5645
telemt_me_refill_failed_total 567
telemt_me_writer_restored_same_endpoint_total 5031
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 471724
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 5321207564 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 151293183136 (140.90 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 86
```