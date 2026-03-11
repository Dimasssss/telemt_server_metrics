# Server Metrics 2026-03-11 06:21:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 57270.0 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1128973
telemt_connections_bad_total 13234
telemt_handshake_timeouts_total 38321
telemt_upstream_connect_attempt_total 12108
telemt_upstream_connect_success_total 12099
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 20874
telemt_me_reconnect_success_total 9192
telemt_me_reader_eof_total 9998
telemt_me_idle_close_by_peer_total 9998
telemt_me_route_drop_no_conn_total 415286
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1014205
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4754
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 3424
telemt_desync_frames_bucket_total{bucket="1_2"} 1308
telemt_desync_frames_bucket_total{bucket="3_10"} 1787
telemt_desync_frames_bucket_total{bucket="gt_10"} 1659
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9644
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9186
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 1013873
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 13492713488 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 298358239160 (277.87 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57327.0 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433479
telemt_connections_bad_total 4460
telemt_handshake_timeouts_total 21258
telemt_upstream_connect_attempt_total 20781
telemt_upstream_connect_success_total 17873
telemt_upstream_connect_fail_total 2908
telemt_upstream_connect_attempts_per_request{bucket="1"} 20781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2908
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 12876
telemt_me_reconnect_success_total 12052
telemt_me_reader_eof_total 12738
telemt_me_idle_close_by_peer_total 12736
telemt_me_route_drop_no_conn_total 198579
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371419
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1928
telemt_desync_full_logged_total 577
telemt_desync_suppressed_total 1351
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 693
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12191
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12030
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 373689
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 3759090206 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 92074039396 (85.75 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 57326.5 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740428
telemt_connections_bad_total 6424
telemt_handshake_timeouts_total 40792
telemt_upstream_connect_attempt_total 15433
telemt_upstream_connect_success_total 15232
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 15433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 694
telemt_me_reconnect_attempts_total 22362
telemt_me_reconnect_success_total 11289
telemt_me_reader_eof_total 12174
telemt_me_idle_close_by_peer_total 12174
telemt_me_route_drop_no_conn_total 249952
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661525
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1880
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1338
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 11781
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11278
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 662378
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 7870742493 (7.33 GB)
telemt_user_octets_to_client{user="hello"} 195535838409 (182.11 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 57326.9 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563168
telemt_connections_bad_total 53794
telemt_handshake_timeouts_total 58082
telemt_upstream_connect_attempt_total 16337
telemt_upstream_connect_success_total 16337
telemt_upstream_connect_attempts_per_request{bucket="1"} 16337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 642
telemt_me_reconnect_attempts_total 14513
telemt_me_reconnect_success_total 13467
telemt_me_reader_eof_total 14298
telemt_me_idle_close_by_peer_total 14298
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 168679
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436231
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 933
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13624
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13445
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 435796
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 5259748136 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 120096051356 (111.85 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57326.6 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590361
telemt_connections_bad_total 5960
telemt_handshake_timeouts_total 4109
telemt_upstream_connect_attempt_total 16319
telemt_upstream_connect_success_total 16251
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 675
telemt_me_reconnect_attempts_total 17049
telemt_me_reconnect_success_total 13265
telemt_me_reader_eof_total 14012
telemt_me_idle_close_by_peer_total 14012
telemt_me_route_drop_no_conn_total 193072
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536740
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2549
telemt_desync_full_logged_total 987
telemt_desync_suppressed_total 1562
telemt_desync_frames_bucket_total{bucket="1_2"} 916
telemt_desync_frames_bucket_total{bucket="3_10"} 1089
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 13553
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13265
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 536477
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 9456945555 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 189282709198 (176.28 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 69
```