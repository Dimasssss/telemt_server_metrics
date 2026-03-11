# Server Metrics 2026-03-11 08:23:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 64594.8 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330417
telemt_connections_bad_total 15722
telemt_handshake_timeouts_total 39904
telemt_upstream_connect_attempt_total 13356
telemt_upstream_connect_success_total 13347
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 749
telemt_me_reconnect_attempts_total 21775
telemt_me_reconnect_success_total 10090
telemt_me_reader_eof_total 10955
telemt_me_idle_close_by_peer_total 10955
telemt_me_route_drop_no_conn_total 490376
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1204763
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5962
telemt_desync_full_logged_total 1649
telemt_desync_suppressed_total 4313
telemt_desync_frames_bucket_total{bucket="1_2"} 1563
telemt_desync_frames_bucket_total{bucket="3_10"} 2269
telemt_desync_frames_bucket_total{bucket="gt_10"} 2130
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10554
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10084
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1204414
telemt_user_connections_current{user="hello"} 1242
telemt_user_octets_from_client{user="hello"} 16148178600 (15.04 GB)
telemt_user_octets_to_client{user="hello"} 350446774904 (326.38 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64651.6 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516256
telemt_connections_bad_total 7666
telemt_handshake_timeouts_total 28896
telemt_upstream_connect_attempt_total 22366
telemt_upstream_connect_success_total 19445
telemt_upstream_connect_fail_total 2921
telemt_upstream_connect_attempts_per_request{bucket="1"} 22366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2921
telemt_me_keepalive_timeout_total 2058
telemt_me_reconnect_attempts_total 14101
telemt_me_reconnect_success_total 13270
telemt_me_reader_eof_total 14036
telemt_me_idle_close_by_peer_total 14034
telemt_me_route_drop_no_conn_total 219550
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436879
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2127
telemt_desync_full_logged_total 651
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 699
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13426
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13248
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 439120
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 4279321478 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 117689606360 (109.61 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 64651.4 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872335
telemt_connections_bad_total 7187
telemt_handshake_timeouts_total 56954
telemt_upstream_connect_attempt_total 17536
telemt_upstream_connect_success_total 17322
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 17536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 753
telemt_me_reconnect_attempts_total 25378
telemt_me_reconnect_success_total 13019
telemt_me_reader_eof_total 14007
telemt_me_idle_close_by_peer_total 14007
telemt_me_route_drop_no_conn_total 293873
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772022
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2236
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1575
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 894
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 13570
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13008
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 551
telemt_user_connections_total{user="hello"} 772799
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 9154838201 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 233751442717 (217.70 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 64651.9 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659062
telemt_connections_bad_total 60480
telemt_handshake_timeouts_total 64313
telemt_upstream_connect_attempt_total 17950
telemt_upstream_connect_success_total 17950
telemt_upstream_connect_attempts_per_request{bucket="1"} 17950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 683
telemt_me_reconnect_attempts_total 15780
telemt_me_reconnect_success_total 14728
telemt_me_reader_eof_total 15647
telemt_me_idle_close_by_peer_total 15646
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 204759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513114
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1233
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14902
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14706
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 512490
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 6040479704 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 141199364296 (131.50 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64651.5 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691105
telemt_connections_bad_total 5976
telemt_handshake_timeouts_total 6592
telemt_upstream_connect_attempt_total 17829
telemt_upstream_connect_success_total 17757
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 721
telemt_me_reconnect_attempts_total 18208
telemt_me_reconnect_success_total 14419
telemt_me_reader_eof_total 15241
telemt_me_idle_close_by_peer_total 15241
telemt_me_route_drop_no_conn_total 233457
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629573
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2813
telemt_desync_full_logged_total 1061
telemt_desync_suppressed_total 1752
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14719
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14419
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 629267
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 10299223347 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 229575907722 (213.81 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 92
```