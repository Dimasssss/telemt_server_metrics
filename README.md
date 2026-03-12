# Server Metrics 2026-03-12 10:19:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15667.3 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508822
telemt_connections_bad_total 1465
telemt_handshake_timeouts_total 2806
telemt_upstream_connect_attempt_total 3085
telemt_upstream_connect_success_total 3065
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 6125
telemt_me_reconnect_success_total 2240
telemt_me_reader_eof_total 2432
telemt_me_idle_close_by_peer_total 2432
telemt_me_route_drop_no_conn_total 175963
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492787
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2355
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1769
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 869
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2382
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2227
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 492655
telemt_user_connections_current{user="hello"} 1390
telemt_user_octets_from_client{user="hello"} 7878110316 (7.34 GB)
telemt_user_octets_to_client{user="hello"} 134773102972 (125.52 GB)
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45287.6 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290525
telemt_connections_bad_total 3146
telemt_handshake_timeouts_total 8511
telemt_upstream_connect_attempt_total 11456
telemt_upstream_connect_success_total 11450
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 674
telemt_me_reconnect_attempts_total 9038
telemt_me_reconnect_success_total 8992
telemt_me_reader_eof_total 9557
telemt_me_idle_close_by_peer_total 9557
telemt_me_route_drop_no_conn_total 84337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260021
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 524
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9066
telemt_me_writer_restored_same_endpoint_total 8983
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 260459
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 3614593871 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 95706806282 (89.13 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 45287.5 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737563
telemt_connections_bad_total 3698
telemt_handshake_timeouts_total 53845
telemt_upstream_connect_attempt_total 11456
telemt_upstream_connect_success_total 11451
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 8898
telemt_me_reconnect_success_total 8823
telemt_me_reader_eof_total 9271
telemt_me_idle_close_by_peer_total 9271
telemt_me_route_drop_no_conn_total 164140
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467179
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2130
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1497
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 1116
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8833
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8782
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 467432
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 5561825628 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 152481176641 (142.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 45288.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376321
telemt_connections_bad_total 2429
telemt_handshake_timeouts_total 28290
telemt_upstream_connect_attempt_total 12302
telemt_upstream_connect_success_total 12252
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 839
telemt_me_reconnect_attempts_total 10012
telemt_me_reconnect_success_total 9975
telemt_me_reader_eof_total 10584
telemt_me_idle_close_by_peer_total 10584
telemt_me_route_drop_no_conn_total 127595
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317200
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10040
telemt_me_writer_restored_same_endpoint_total 9954
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 317021
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 3833077432 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 123935208500 (115.42 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45287.8 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424858
telemt_connections_bad_total 468
telemt_handshake_timeouts_total 3255
telemt_upstream_connect_attempt_total 14762
telemt_upstream_connect_success_total 14589
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 14762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 627
telemt_me_reconnect_attempts_total 13826
telemt_me_reconnect_success_total 12302
telemt_me_reader_eof_total 12817
telemt_me_idle_close_by_peer_total 12817
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 137494
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400880
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1700
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1142
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 608
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12470
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12280
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 400806
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 4457550628 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 96201197888 (89.59 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 112
```