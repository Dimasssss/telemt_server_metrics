# Server Metrics 2026-03-14 21:10:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 28353.7 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1052801
telemt_connections_bad_total 42369
telemt_handshake_timeouts_total 14732
telemt_upstream_connect_attempt_total 5177
telemt_upstream_connect_success_total 5154
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4499
telemt_me_reconnect_success_total 3691
telemt_me_reader_eof_total 3894
telemt_me_idle_close_by_peer_total 3894
telemt_me_route_drop_no_conn_total 402173
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937456
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3144
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 2238
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 1168
telemt_desync_frames_bucket_total{bucket="gt_10"} 1236
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3774
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3682
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 937395
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 16682643636 (15.54 GB)
telemt_user_octets_to_client{user="hello"} 315338077520 (293.68 GB)
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 28358.9 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414585
telemt_connections_bad_total 31468
telemt_handshake_timeouts_total 12917
telemt_upstream_connect_attempt_total 6098
telemt_upstream_connect_success_total 6038
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 6098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 480
telemt_me_reconnect_attempts_total 5374
telemt_me_reconnect_success_total 4576
telemt_me_reader_eof_total 4788
telemt_me_idle_close_by_peer_total 4788
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 121785
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346652
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1704
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1256
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 407
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4695
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4553
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 346596
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 5506272740 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 120235802340 (111.98 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 28221.8 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899708
telemt_connections_bad_total 3729
telemt_handshake_timeouts_total 223560
telemt_upstream_connect_attempt_total 5500
telemt_upstream_connect_success_total 5483
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 7947
telemt_me_reconnect_success_total 4034
telemt_me_reader_eof_total 4325
telemt_me_idle_close_by_peer_total 4325
telemt_me_route_drop_no_conn_total 202253
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575200
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2169
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 759
telemt_desync_frames_bucket_total{bucket="gt_10"} 1091
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4201
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4001
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 575027
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 8926699748 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 215937720616 (201.11 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 28076.3 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478468
telemt_connections_bad_total 100407
telemt_handshake_timeouts_total 54968
telemt_upstream_connect_attempt_total 6476
telemt_upstream_connect_success_total 6475
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 5956
telemt_me_reconnect_success_total 5033
telemt_me_reader_eof_total 5284
telemt_me_idle_close_by_peer_total 5284
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 110636
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315002
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 702
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5120
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5021
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 314916
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 4432099848 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 96154489960 (89.55 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 28371.6 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401220
telemt_connections_bad_total 1391
telemt_handshake_timeouts_total 3985
telemt_upstream_connect_attempt_total 6031
telemt_upstream_connect_success_total 5912
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 6031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 5146
telemt_me_reconnect_success_total 4469
telemt_me_reader_eof_total 4721
telemt_me_idle_close_by_peer_total 4721
telemt_me_route_drop_no_conn_total 126531
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372550
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1019
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 661
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4571
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4451
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 372514
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 5942073244 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 154566120040 (143.95 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 70
```