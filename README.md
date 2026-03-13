# Server Metrics 2026-03-13 23:10:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 148288.2 (41h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4558397
telemt_connections_bad_total 38380
telemt_handshake_timeouts_total 107598
telemt_upstream_connect_attempt_total 31035
telemt_upstream_connect_success_total 30822
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 31035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 6645
telemt_me_reconnect_attempts_total 31231
telemt_me_reconnect_success_total 21104
telemt_me_reader_eof_total 22637
telemt_me_idle_close_by_peer_total 22636
telemt_me_route_drop_no_conn_total 1723293
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4176537
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16591
telemt_desync_full_logged_total 4467
telemt_desync_suppressed_total 12124
telemt_desync_frames_bucket_total{bucket="1_2"} 4131
telemt_desync_frames_bucket_total{bucket="3_10"} 6345
telemt_desync_frames_bucket_total{bucket="gt_10"} 6115
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 21725
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21091
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 4178469
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 61349955948 (57.14 GB)
telemt_user_octets_to_client{user="hello"} 1321077211981 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47951.9 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 605044
telemt_connections_bad_total 44312
telemt_handshake_timeouts_total 12542
telemt_upstream_connect_attempt_total 13614
telemt_upstream_connect_success_total 13378
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 13614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 1917
telemt_me_reconnect_attempts_total 12362
telemt_me_reconnect_success_total 8925
telemt_me_reader_eof_total 9464
telemt_me_idle_close_by_peer_total 9463
telemt_me_route_drop_no_conn_total 219303
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522207
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 9165
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8917
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 524150
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 5774505357 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 170440083980 (158.73 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 177908.7 (49h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3307736
telemt_connections_bad_total 31835
telemt_handshake_timeouts_total 221355
telemt_upstream_connect_attempt_total 39498
telemt_upstream_connect_success_total 39477
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10333
telemt_me_reconnect_attempts_total 35257
telemt_me_reconnect_success_total 30304
telemt_me_reader_eof_total 32166
telemt_me_idle_close_by_peer_total 32165
telemt_me_route_drop_no_conn_total 1134303
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2747777
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9000
telemt_desync_full_logged_total 3030
telemt_desync_suppressed_total 5970
telemt_desync_frames_bucket_total{bucket="1_2"} 1513
telemt_desync_frames_bucket_total{bucket="3_10"} 3260
telemt_desync_frames_bucket_total{bucket="gt_10"} 4227
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 30748
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30263
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 2747029
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 44699832632 (41.63 GB)
telemt_user_octets_to_client{user="hello"} 971151370857 (904.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 177911.2 (49h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2171981
telemt_connections_bad_total 22848
telemt_handshake_timeouts_total 226633
telemt_upstream_connect_attempt_total 55416
telemt_upstream_connect_success_total 52965
telemt_upstream_connect_fail_total 2314
telemt_upstream_connect_attempts_per_request{bucket="1"} 55142
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2313
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20345
telemt_me_reconnect_attempts_total 46105
telemt_me_reconnect_success_total 37086
telemt_me_reader_eof_total 39775
telemt_me_idle_close_by_peer_total 39768
telemt_me_route_drop_no_conn_total 758871
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1765262
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 37687
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37062
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 1771148
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 27329155407 (25.45 GB)
telemt_user_octets_to_client{user="hello"} 660949830226 (615.56 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47344.4 (13h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650506
telemt_connections_bad_total 7853
telemt_handshake_timeouts_total 6914
telemt_upstream_connect_attempt_total 10853
telemt_upstream_connect_success_total 10514
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 10853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 1435
telemt_me_reconnect_attempts_total 37853
telemt_me_reconnect_success_total 8135
telemt_me_reader_eof_total 9209
telemt_me_idle_close_by_peer_total 9208
telemt_me_route_drop_no_conn_total 246688
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606247
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1603
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1099
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9135
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 8130
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 606153
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 9688773772 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 198752672380 (185.10 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 34
```