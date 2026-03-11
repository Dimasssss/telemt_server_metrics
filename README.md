# Server Metrics 2026-03-11 08:33:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 65205.3 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349154
telemt_connections_bad_total 15723
telemt_handshake_timeouts_total 39985
telemt_upstream_connect_attempt_total 13519
telemt_upstream_connect_success_total 13510
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 749
telemt_me_reconnect_attempts_total 21893
telemt_me_reconnect_success_total 10207
telemt_me_reader_eof_total 11073
telemt_me_idle_close_by_peer_total 11073
telemt_me_route_drop_no_conn_total 497393
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1222879
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6014
telemt_desync_full_logged_total 1671
telemt_desync_suppressed_total 4343
telemt_desync_frames_bucket_total{bucket="1_2"} 1581
telemt_desync_frames_bucket_total{bucket="3_10"} 2288
telemt_desync_frames_bucket_total{bucket="gt_10"} 2145
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10672
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10201
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1222550
telemt_user_connections_current{user="hello"} 1245
telemt_user_octets_from_client{user="hello"} 16321530448 (15.20 GB)
telemt_user_octets_to_client{user="hello"} 354443798668 (330.10 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65262.1 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523084
telemt_connections_bad_total 8347
telemt_handshake_timeouts_total 28998
telemt_upstream_connect_attempt_total 22536
telemt_upstream_connect_success_total 19612
telemt_upstream_connect_fail_total 2924
telemt_upstream_connect_attempts_per_request{bucket="1"} 22536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2924
telemt_me_keepalive_timeout_total 2061
telemt_me_reconnect_attempts_total 14225
telemt_me_reconnect_success_total 13394
telemt_me_reader_eof_total 14174
telemt_me_idle_close_by_peer_total 14172
telemt_me_route_drop_no_conn_total 221837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442798
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2136
telemt_desync_full_logged_total 654
telemt_desync_suppressed_total 1482
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13550
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13372
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 445040
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 4332511086 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 119062139956 (110.89 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 65262.0 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886961
telemt_connections_bad_total 7188
telemt_handshake_timeouts_total 60809
telemt_upstream_connect_attempt_total 17687
telemt_upstream_connect_success_total 17472
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 17687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 755
telemt_me_reconnect_attempts_total 25485
telemt_me_reconnect_success_total 13125
telemt_me_reader_eof_total 14120
telemt_me_idle_close_by_peer_total 14120
telemt_me_route_drop_no_conn_total 297738
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781490
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2244
telemt_desync_full_logged_total 664
telemt_desync_suppressed_total 1580
telemt_desync_frames_bucket_total{bucket="1_2"} 532
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 896
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 13676
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13114
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 551
telemt_user_connections_total{user="hello"} 782273
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 9241662785 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 236581996941 (220.33 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 65262.4 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668042
telemt_connections_bad_total 61032
telemt_handshake_timeouts_total 65029
telemt_upstream_connect_attempt_total 18107
telemt_upstream_connect_success_total 18107
telemt_upstream_connect_attempts_per_request{bucket="1"} 18107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 685
telemt_me_reconnect_attempts_total 15894
telemt_me_reconnect_success_total 14842
telemt_me_reader_eof_total 15771
telemt_me_idle_close_by_peer_total 15770
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 207701
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520718
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1234
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 15018
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14820
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 520094
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 6117829672 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 142701986040 (132.90 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65262.0 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702029
telemt_connections_bad_total 5980
telemt_handshake_timeouts_total 6678
telemt_upstream_connect_attempt_total 17977
telemt_upstream_connect_success_total 17905
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 723
telemt_me_reconnect_attempts_total 18313
telemt_me_reconnect_success_total 14522
telemt_me_reader_eof_total 15353
telemt_me_idle_close_by_peer_total 15353
telemt_me_route_drop_no_conn_total 237071
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638370
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2829
telemt_desync_full_logged_total 1067
telemt_desync_suppressed_total 1762
telemt_desync_frames_bucket_total{bucket="1_2"} 990
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 14824
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14522
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 638062
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 10407393895 (9.69 GB)
telemt_user_octets_to_client{user="hello"} 231727371074 (215.81 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 121
```