# Server Metrics 2026-03-11 03:23:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 46599.8 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895300
telemt_connections_bad_total 10070
telemt_handshake_timeouts_total 21269
telemt_upstream_connect_attempt_total 10086
telemt_upstream_connect_success_total 10077
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 19371
telemt_me_reconnect_success_total 7700
telemt_me_reader_eof_total 8401
telemt_me_idle_close_by_peer_total 8401
telemt_me_route_drop_no_conn_total 351489
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830368
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3855
telemt_desync_full_logged_total 1069
telemt_desync_suppressed_total 2786
telemt_desync_frames_bucket_total{bucket="1_2"} 1101
telemt_desync_frames_bucket_total{bucket="3_10"} 1447
telemt_desync_frames_bucket_total{bucket="gt_10"} 1307
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8132
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7694
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 830098
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 11114717944 (10.35 GB)
telemt_user_octets_to_client{user="hello"} 247214748024 (230.24 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46656.4 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370554
telemt_connections_bad_total 2487
telemt_handshake_timeouts_total 18427
telemt_upstream_connect_attempt_total 18060
telemt_upstream_connect_success_total 15168
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1760
telemt_me_reconnect_attempts_total 10693
telemt_me_reconnect_success_total 9876
telemt_me_reader_eof_total 10424
telemt_me_idle_close_by_peer_total 10422
telemt_me_route_drop_no_conn_total 179953
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317543
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1803
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 9993
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9855
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 319813
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 3055047042 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 75084081500 (69.93 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 46656.3 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 620615
telemt_connections_bad_total 5342
telemt_handshake_timeouts_total 34796
telemt_upstream_connect_attempt_total 12625
telemt_upstream_connect_success_total 12461
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 12625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 549
telemt_me_reconnect_attempts_total 20110
telemt_me_reconnect_success_total 9041
telemt_me_reader_eof_total 9809
telemt_me_idle_close_by_peer_total 9809
telemt_me_route_drop_no_conn_total 210668
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551415
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1606
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 9507
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9030
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 552309
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 7101471861 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 168296169669 (156.74 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 46656.7 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467540
telemt_connections_bad_total 44061
telemt_handshake_timeouts_total 45714
telemt_upstream_connect_attempt_total 13580
telemt_upstream_connect_success_total 13580
telemt_upstream_connect_attempts_per_request{bucket="1"} 13580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 469
telemt_me_reconnect_attempts_total 12276
telemt_me_reconnect_success_total 11238
telemt_me_reader_eof_total 11922
telemt_me_idle_close_by_peer_total 11922
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 139578
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363973
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 785
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 11370
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11219
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 363641
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 4422543728 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 96894728020 (90.24 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46656.3 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493855
telemt_connections_bad_total 5811
telemt_handshake_timeouts_total 3071
telemt_upstream_connect_attempt_total 13660
telemt_upstream_connect_success_total 13601
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 14995
telemt_me_reconnect_success_total 11215
telemt_me_reader_eof_total 11833
telemt_me_idle_close_by_peer_total 11833
telemt_me_route_drop_no_conn_total 158571
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449697
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2337
telemt_desync_full_logged_total 913
telemt_desync_suppressed_total 1424
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 479
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 11477
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11215
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 449349
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 8599593976 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 161657994572 (150.56 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 45
```