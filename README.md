# Server Metrics 2026-03-13 19:15:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 134205.5 (37h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4289608
telemt_connections_bad_total 37751
telemt_handshake_timeouts_total 104635
telemt_upstream_connect_attempt_total 28188
telemt_upstream_connect_success_total 27996
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 28188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 6522
telemt_me_reconnect_attempts_total 29056
telemt_me_reconnect_success_total 18940
telemt_me_reader_eof_total 20330
telemt_me_idle_close_by_peer_total 20329
telemt_me_route_drop_no_conn_total 1609444
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3921814
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15446
telemt_desync_full_logged_total 4111
telemt_desync_suppressed_total 11335
telemt_desync_frames_bucket_total{bucket="1_2"} 3848
telemt_desync_frames_bucket_total{bucket="3_10"} 5878
telemt_desync_frames_bucket_total{bucket="gt_10"} 5720
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19527
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18927
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 3923984
telemt_user_connections_current{user="hello"} 1642
telemt_user_octets_from_client{user="hello"} 56819998572 (52.92 GB)
telemt_user_octets_to_client{user="hello"} 1232643807641 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33869.3 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494538
telemt_connections_bad_total 38555
telemt_handshake_timeouts_total 10959
telemt_upstream_connect_attempt_total 10026
telemt_upstream_connect_success_total 9813
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 1865
telemt_me_reconnect_attempts_total 9489
telemt_me_reconnect_success_total 6076
telemt_me_reader_eof_total 6423
telemt_me_idle_close_by_peer_total 6422
telemt_me_route_drop_no_conn_total 186066
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430253
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1511
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 1107
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 523
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6266
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6068
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 432181
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 4567486161 (4.25 GB)
telemt_user_octets_to_client{user="hello"} 136248403988 (126.89 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 163826.0 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3135468
telemt_connections_bad_total 29160
telemt_handshake_timeouts_total 210568
telemt_upstream_connect_attempt_total 36396
telemt_upstream_connect_success_total 36381
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10174
telemt_me_reconnect_attempts_total 30482
telemt_me_reconnect_success_total 27919
telemt_me_reader_eof_total 29588
telemt_me_idle_close_by_peer_total 29587
telemt_me_route_drop_no_conn_total 1071143
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2591501
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8695
telemt_desync_full_logged_total 2876
telemt_desync_suppressed_total 5819
telemt_desync_frames_bucket_total{bucket="1_2"} 1425
telemt_desync_frames_bucket_total{bucket="3_10"} 3181
telemt_desync_frames_bucket_total{bucket="gt_10"} 4089
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 28250
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27878
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 2590791
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 42471228496 (39.55 GB)
telemt_user_octets_to_client{user="hello"} 909789224985 (847.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 163826.4 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2020111
telemt_connections_bad_total 21617
telemt_handshake_timeouts_total 184849
telemt_upstream_connect_attempt_total 51531
telemt_upstream_connect_success_total 49097
telemt_upstream_connect_fail_total 2297
telemt_upstream_connect_attempts_per_request{bucket="1"} 51257
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2296
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20183
telemt_me_reconnect_attempts_total 42936
telemt_me_reconnect_success_total 33931
telemt_me_reader_eof_total 36429
telemt_me_idle_close_by_peer_total 36422
telemt_me_route_drop_no_conn_total 717994
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1668102
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3516
telemt_desync_full_logged_total 1125
telemt_desync_suppressed_total 2391
telemt_desync_frames_bucket_total{bucket="1_2"} 942
telemt_desync_frames_bucket_total{bucket="3_10"} 1447
telemt_desync_frames_bucket_total{bucket="gt_10"} 1127
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 34492
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33907
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 1673973
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 25607461691 (23.85 GB)
telemt_user_octets_to_client{user="hello"} 633739212666 (590.22 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33262.0 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535598
telemt_connections_bad_total 5599
telemt_handshake_timeouts_total 5302
telemt_upstream_connect_attempt_total 7142
telemt_upstream_connect_success_total 6904
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 7142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 954
telemt_me_reconnect_attempts_total 26171
telemt_me_reconnect_success_total 5236
telemt_me_reader_eof_total 5980
telemt_me_idle_close_by_peer_total 5979
telemt_me_route_drop_no_conn_total 203649
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501448
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1454
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5932
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5232
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 501423
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 5813943788 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 161573847480 (150.48 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 83
```