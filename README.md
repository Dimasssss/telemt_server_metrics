# Server Metrics 2026-03-10 19:15:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17293.1 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550354
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 3363
telemt_upstream_connect_attempt_total 3514
telemt_upstream_connect_success_total 3505
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 13014
telemt_me_reconnect_success_total 2554
telemt_me_reader_eof_total 2887
telemt_me_idle_close_by_peer_total 2887
telemt_me_route_drop_no_conn_total 229399
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519835
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2699
telemt_desync_full_logged_total 736
telemt_desync_suppressed_total 1963
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 942
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2892
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2548
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 519741
telemt_user_connections_current{user="hello"} 1097
telemt_user_octets_from_client{user="hello"} 7745466792 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 150312459052 (139.99 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17349.8 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238886
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16484
telemt_upstream_connect_attempt_total 8808
telemt_upstream_connect_success_total 6064
telemt_upstream_connect_fail_total 2744
telemt_upstream_connect_attempts_per_request{bucket="1"} 8808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2744
telemt_me_keepalive_timeout_total 706
telemt_me_reconnect_attempts_total 3936
telemt_me_reconnect_success_total 3152
telemt_me_reader_eof_total 3295
telemt_me_idle_close_by_peer_total 3293
telemt_me_route_drop_no_conn_total 130585
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202060
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 870
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 619
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3209
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3131
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 204018
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 2181739842 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 48961393650 (45.60 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 17349.6 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396498
telemt_connections_bad_total 1332
telemt_handshake_timeouts_total 31980
telemt_upstream_connect_attempt_total 5339
telemt_upstream_connect_success_total 5256
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 5339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 6721
telemt_me_reconnect_success_total 3273
telemt_me_reader_eof_total 3489
telemt_me_idle_close_by_peer_total 3489
telemt_me_route_drop_no_conn_total 133934
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338263
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1078
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 777
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3440
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3262
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 339215
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 4707673421 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 107845194269 (100.44 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 17350.2 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259865
telemt_connections_bad_total 17139
telemt_handshake_timeouts_total 23089
telemt_upstream_connect_attempt_total 4796
telemt_upstream_connect_success_total 4796
telemt_upstream_connect_attempts_per_request{bucket="1"} 4796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 4882
telemt_me_reconnect_success_total 3868
telemt_me_reader_eof_total 4045
telemt_me_idle_close_by_peer_total 4045
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 85438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208748
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3939
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 3855
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 208522
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 3387778252 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 61387337332 (57.17 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17349.7 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274417
telemt_connections_bad_total 817
telemt_handshake_timeouts_total 1862
telemt_upstream_connect_attempt_total 5284
telemt_upstream_connect_success_total 5265
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 5284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 4351
telemt_me_reconnect_success_total 4318
telemt_me_reader_eof_total 4447
telemt_me_idle_close_by_peer_total 4447
telemt_me_route_drop_no_conn_total 102164
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259292
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1441
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 604
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4381
telemt_me_writer_restored_same_endpoint_total 4318
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 259222
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 5342387236 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 81375703884 (75.79 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 94
```