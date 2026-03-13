# Server Metrics 2026-03-13 19:25:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 134817.2 (37h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4307039
telemt_connections_bad_total 37751
telemt_handshake_timeouts_total 105278
telemt_upstream_connect_attempt_total 28279
telemt_upstream_connect_success_total 28087
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 28279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 6525
telemt_me_reconnect_attempts_total 29147
telemt_me_reconnect_success_total 19030
telemt_me_reader_eof_total 20428
telemt_me_idle_close_by_peer_total 20427
telemt_me_route_drop_no_conn_total 1617015
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3938007
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15489
telemt_desync_full_logged_total 4128
telemt_desync_suppressed_total 11361
telemt_desync_frames_bucket_total{bucket="1_2"} 3858
telemt_desync_frames_bucket_total{bucket="3_10"} 5896
telemt_desync_frames_bucket_total{bucket="gt_10"} 5735
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19619
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19017
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 3940177
telemt_user_connections_current{user="hello"} 1346
telemt_user_octets_from_client{user="hello"} 57076302808 (53.16 GB)
telemt_user_octets_to_client{user="hello"} 1238952281261 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 382
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34481.1 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 501720
telemt_connections_bad_total 39067
telemt_handshake_timeouts_total 11087
telemt_upstream_connect_attempt_total 10166
telemt_upstream_connect_success_total 9953
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 1868
telemt_me_reconnect_attempts_total 9586
telemt_me_reconnect_success_total 6173
telemt_me_reader_eof_total 6528
telemt_me_idle_close_by_peer_total 6527
telemt_me_route_drop_no_conn_total 188168
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436506
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1523
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 1115
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 527
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6365
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6165
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 438437
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 4653309153 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 138836707096 (129.30 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 164437.7 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3147728
telemt_connections_bad_total 29280
telemt_handshake_timeouts_total 211926
telemt_upstream_connect_attempt_total 36540
telemt_upstream_connect_success_total 36525
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10178
telemt_me_reconnect_attempts_total 30585
telemt_me_reconnect_success_total 28022
telemt_me_reader_eof_total 29700
telemt_me_idle_close_by_peer_total 29699
telemt_me_route_drop_no_conn_total 1076024
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2602070
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8705
telemt_desync_full_logged_total 2881
telemt_desync_suppressed_total 5824
telemt_desync_frames_bucket_total{bucket="1_2"} 1431
telemt_desync_frames_bucket_total{bucket="3_10"} 3183
telemt_desync_frames_bucket_total{bucket="gt_10"} 4091
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 28356
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27981
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 2601358
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 43125131772 (40.16 GB)
telemt_user_octets_to_client{user="hello"} 912754481545 (850.07 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 164438.1 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2029802
telemt_connections_bad_total 21812
telemt_handshake_timeouts_total 186403
telemt_upstream_connect_attempt_total 51678
telemt_upstream_connect_success_total 49244
telemt_upstream_connect_fail_total 2297
telemt_upstream_connect_attempts_per_request{bucket="1"} 51404
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2296
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20183
telemt_me_reconnect_attempts_total 43040
telemt_me_reconnect_success_total 34035
telemt_me_reader_eof_total 36542
telemt_me_idle_close_by_peer_total 36535
telemt_me_route_drop_no_conn_total 720356
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1675950
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3560
telemt_desync_full_logged_total 1137
telemt_desync_suppressed_total 2423
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 1479
telemt_desync_frames_bucket_total{bucket="gt_10"} 1134
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 34597
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34011
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 1681820
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 25727755667 (23.96 GB)
telemt_user_octets_to_client{user="hello"} 635566057762 (591.92 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33873.7 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542635
telemt_connections_bad_total 5639
telemt_handshake_timeouts_total 5345
telemt_upstream_connect_attempt_total 7287
telemt_upstream_connect_success_total 7049
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 7287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 956
telemt_me_reconnect_attempts_total 26273
telemt_me_reconnect_success_total 5338
telemt_me_reader_eof_total 6088
telemt_me_idle_close_by_peer_total 6087
telemt_me_route_drop_no_conn_total 206069
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508137
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 6034
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5334
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 508111
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 5940056052 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 163878793912 (152.62 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 59
```