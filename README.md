# Server Metrics 2026-03-12 14:24:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 30355.3 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079559
telemt_connections_bad_total 14601
telemt_handshake_timeouts_total 11281
telemt_upstream_connect_attempt_total 5964
telemt_upstream_connect_success_total 5930
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 8287
telemt_me_reconnect_success_total 4388
telemt_me_reader_eof_total 4691
telemt_me_idle_close_by_peer_total 4690
telemt_me_route_drop_no_conn_total 381464
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019158
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5507
telemt_desync_full_logged_total 1382
telemt_desync_suppressed_total 4125
telemt_desync_frames_bucket_total{bucket="1_2"} 1392
telemt_desync_frames_bucket_total{bucket="3_10"} 1985
telemt_desync_frames_bucket_total{bucket="gt_10"} 2130
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4561
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4375
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1018910
telemt_user_connections_current{user="hello"} 1583
telemt_user_octets_from_client{user="hello"} 16438997228 (15.31 GB)
telemt_user_octets_to_client{user="hello"} 298216812852 (277.74 GB)
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59975.9 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503853
telemt_connections_bad_total 5356
telemt_handshake_timeouts_total 25785
telemt_upstream_connect_attempt_total 14302
telemt_upstream_connect_success_total 14295
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1143
telemt_me_reconnect_attempts_total 11185
telemt_me_reconnect_success_total 11124
telemt_me_reader_eof_total 11833
telemt_me_idle_close_by_peer_total 11833
telemt_me_route_drop_no_conn_total 146369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448339
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1660
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1134
telemt_desync_frames_bucket_total{bucket="1_2"} 702
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11227
telemt_me_writer_restored_same_endpoint_total 11115
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 448799
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 6857790879 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 159979129770 (148.99 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 59975.8 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090439
telemt_connections_bad_total 5730
telemt_handshake_timeouts_total 79060
telemt_upstream_connect_attempt_total 14393
telemt_upstream_connect_success_total 14388
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 11135
telemt_me_reconnect_success_total 11035
telemt_me_reader_eof_total 11615
telemt_me_idle_close_by_peer_total 11615
telemt_me_route_drop_no_conn_total 285127
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 783672
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3284
telemt_desync_full_logged_total 1008
telemt_desync_suppressed_total 2276
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 1614
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11078
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10994
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 783860
telemt_user_connections_current{user="hello"} 1009
telemt_user_octets_from_client{user="hello"} 10280728292 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 250149276809 (232.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 59976.2 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633446
telemt_connections_bad_total 7688
telemt_handshake_timeouts_total 56089
telemt_upstream_connect_attempt_total 15870
telemt_upstream_connect_success_total 15806
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1332
telemt_me_reconnect_attempts_total 14046
telemt_me_reconnect_success_total 12811
telemt_me_reader_eof_total 13581
telemt_me_idle_close_by_peer_total 13581
telemt_me_route_drop_no_conn_total 214265
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537634
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1088
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 709
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 446
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12947
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12790
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 537137
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 5888657152 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 217278934548 (202.36 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59975.9 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716164
telemt_connections_bad_total 4281
telemt_handshake_timeouts_total 5737
telemt_upstream_connect_attempt_total 18763
telemt_upstream_connect_success_total 18536
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 18763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1055
telemt_me_reconnect_attempts_total 22768
telemt_me_reconnect_success_total 15540
telemt_me_reader_eof_total 16298
telemt_me_idle_close_by_peer_total 16298
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 246732
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663885
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2719
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 1803
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 942
telemt_desync_frames_bucket_total{bucket="gt_10"} 1002
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 15924
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15509
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 384
telemt_user_connections_total{user="hello"} 663786
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 7736205368 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 180426894348 (168.04 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 120
```