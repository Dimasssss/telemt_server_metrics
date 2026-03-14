# Server Metrics 2026-03-14 00:31:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 153195.3 (42h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4603573
telemt_connections_bad_total 38412
telemt_handshake_timeouts_total 107863
telemt_upstream_connect_attempt_total 32250
telemt_upstream_connect_success_total 32032
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6662
telemt_me_reconnect_attempts_total 32176
telemt_me_reconnect_success_total 22044
telemt_me_reader_eof_total 23650
telemt_me_idle_close_by_peer_total 23649
telemt_me_route_drop_no_conn_total 1742633
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4220081
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16632
telemt_desync_full_logged_total 4483
telemt_desync_suppressed_total 12149
telemt_desync_frames_bucket_total{bucket="1_2"} 4142
telemt_desync_frames_bucket_total{bucket="3_10"} 6362
telemt_desync_frames_bucket_total{bucket="gt_10"} 6128
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 22678
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22031
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 4221958
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 62290220820 (58.01 GB)
telemt_user_octets_to_client{user="hello"} 1334482739777 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52858.9 (14h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646604
telemt_connections_bad_total 48234
telemt_handshake_timeouts_total 12835
telemt_upstream_connect_attempt_total 14867
telemt_upstream_connect_success_total 14625
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 14867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 1941
telemt_me_reconnect_attempts_total 13393
telemt_me_reconnect_success_total 9951
telemt_me_reader_eof_total 10555
telemt_me_idle_close_by_peer_total 10554
telemt_me_route_drop_no_conn_total 225921
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535854
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
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10198
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9943
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 537805
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 5852769069 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 174793038904 (162.79 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 182815.9 (50h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3335234
telemt_connections_bad_total 32602
telemt_handshake_timeouts_total 222418
telemt_upstream_connect_attempt_total 40866
telemt_upstream_connect_success_total 40845
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10352
telemt_me_reconnect_attempts_total 36363
telemt_me_reconnect_success_total 31407
telemt_me_reader_eof_total 33338
telemt_me_idle_close_by_peer_total 33337
telemt_me_route_drop_no_conn_total 1144868
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2772830
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9129
telemt_desync_full_logged_total 3067
telemt_desync_suppressed_total 6062
telemt_desync_frames_bucket_total{bucket="1_2"} 1537
telemt_desync_frames_bucket_total{bucket="3_10"} 3310
telemt_desync_frames_bucket_total{bucket="gt_10"} 4282
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 31861
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31366
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 2772070
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 44879512176 (41.80 GB)
telemt_user_octets_to_client{user="hello"} 984575185001 (916.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 182818.4 (50h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2210534
telemt_connections_bad_total 22883
telemt_handshake_timeouts_total 237287
telemt_upstream_connect_attempt_total 56887
telemt_upstream_connect_success_total 54431
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 56613
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2318
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20381
telemt_me_reconnect_attempts_total 47313
telemt_me_reconnect_success_total 38287
telemt_me_reader_eof_total 41068
telemt_me_idle_close_by_peer_total 41061
telemt_me_route_drop_no_conn_total 764616
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1779813
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 38899
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38263
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 1785723
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 27384613135 (25.50 GB)
telemt_user_octets_to_client{user="hello"} 663066140826 (617.53 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52251.8 (14h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673542
telemt_connections_bad_total 7870
telemt_handshake_timeouts_total 8602
telemt_upstream_connect_attempt_total 12594
telemt_upstream_connect_success_total 12233
telemt_upstream_connect_fail_total 361
telemt_upstream_connect_attempts_per_request{bucket="1"} 12594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 361
telemt_me_keepalive_timeout_total 1462
telemt_me_reconnect_attempts_total 41774
telemt_me_reconnect_success_total 9617
telemt_me_reader_eof_total 10819
telemt_me_idle_close_by_peer_total 10818
telemt_me_route_drop_no_conn_total 254011
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 626219
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 10708
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9612
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1091
telemt_user_connections_total{user="hello"} 626118
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 10524740204 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 205052575336 (190.97 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```