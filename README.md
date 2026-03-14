# Server Metrics 2026-03-14 01:23:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 156263.1 (43h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4631689
telemt_connections_bad_total 39794
telemt_handshake_timeouts_total 108077
telemt_upstream_connect_attempt_total 33035
telemt_upstream_connect_success_total 32815
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 33035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 6682
telemt_me_reconnect_attempts_total 32829
telemt_me_reconnect_success_total 22695
telemt_me_reader_eof_total 24335
telemt_me_idle_close_by_peer_total 24334
telemt_me_route_drop_no_conn_total 1753725
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4245640
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16695
telemt_desync_full_logged_total 4502
telemt_desync_suppressed_total 12193
telemt_desync_frames_bucket_total{bucket="1_2"} 4167
telemt_desync_frames_bucket_total{bucket="3_10"} 6375
telemt_desync_frames_bucket_total{bucket="gt_10"} 6153
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 23335
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22682
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 4247497
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 62594381720 (58.30 GB)
telemt_user_octets_to_client{user="hello"} 1342639528921 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55927.9 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 675790
telemt_connections_bad_total 50707
telemt_handshake_timeouts_total 12951
telemt_upstream_connect_attempt_total 15629
telemt_upstream_connect_success_total 15381
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 15629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 2046
telemt_me_reconnect_attempts_total 13976
telemt_me_reconnect_success_total 10533
telemt_me_reader_eof_total 11173
telemt_me_idle_close_by_peer_total 11172
telemt_me_route_drop_no_conn_total 229733
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545782
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1650
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10788
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 547733
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 5921020889 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 177124619852 (164.96 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 185883.4 (51h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3352953
telemt_connections_bad_total 34317
telemt_handshake_timeouts_total 222846
telemt_upstream_connect_attempt_total 41748
telemt_upstream_connect_success_total 41727
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10377
telemt_me_reconnect_attempts_total 37116
telemt_me_reconnect_success_total 32157
telemt_me_reader_eof_total 34141
telemt_me_idle_close_by_peer_total 34140
telemt_me_route_drop_no_conn_total 1150643
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2788002
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9170
telemt_desync_full_logged_total 3081
telemt_desync_suppressed_total 6089
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 3320
telemt_desync_frames_bucket_total{bucket="gt_10"} 4305
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 32612
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32116
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2787240
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 44975669384 (41.89 GB)
telemt_user_octets_to_client{user="hello"} 993791629577 (925.54 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 185886.1 (51h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2231989
telemt_connections_bad_total 22927
telemt_handshake_timeouts_total 241414
telemt_upstream_connect_attempt_total 58034
telemt_upstream_connect_success_total 55574
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 57759
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20389
telemt_me_reconnect_attempts_total 48326
telemt_me_reconnect_success_total 39297
telemt_me_reader_eof_total 42151
telemt_me_idle_close_by_peer_total 42144
telemt_me_route_drop_no_conn_total 767768
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1788859
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3801
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 39921
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39273
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 624
telemt_user_connections_total{user="hello"} 1794774
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 27417612019 (25.53 GB)
telemt_user_octets_to_client{user="hello"} 664332800534 (618.71 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55319.5 (15h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683829
telemt_connections_bad_total 7886
telemt_handshake_timeouts_total 8624
telemt_upstream_connect_attempt_total 13783
telemt_upstream_connect_success_total 13398
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 13783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_keepalive_timeout_total 1480
telemt_me_reconnect_attempts_total 42777
telemt_me_reconnect_success_total 10619
telemt_me_reader_eof_total 11877
telemt_me_idle_close_by_peer_total 11876
telemt_me_route_drop_no_conn_total 259220
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636299
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11714
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10614
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1095
telemt_user_connections_total{user="hello"} 636194
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 10570351276 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 207972941560 (193.69 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 29
```