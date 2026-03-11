# Server Metrics 2026-03-11 09:34:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 68872.5 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1471612
telemt_connections_bad_total 19589
telemt_handshake_timeouts_total 40674
telemt_upstream_connect_attempt_total 14337
telemt_upstream_connect_success_total 14328
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 780
telemt_me_reconnect_attempts_total 22536
telemt_me_reconnect_success_total 10848
telemt_me_reader_eof_total 11753
telemt_me_idle_close_by_peer_total 11753
telemt_me_route_drop_no_conn_total 543313
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1336306
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6550
telemt_desync_full_logged_total 1815
telemt_desync_suppressed_total 4735
telemt_desync_frames_bucket_total{bucket="1_2"} 1730
telemt_desync_frames_bucket_total{bucket="3_10"} 2489
telemt_desync_frames_bucket_total{bucket="gt_10"} 2331
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11317
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10842
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 1334845
telemt_user_connections_current{user="hello"} 1308
telemt_user_octets_from_client{user="hello"} 17560141588 (16.35 GB)
telemt_user_octets_to_client{user="hello"} 383696560716 (357.35 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68929.4 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564614
telemt_connections_bad_total 9820
telemt_handshake_timeouts_total 30736
telemt_upstream_connect_attempt_total 23295
telemt_upstream_connect_success_total 20366
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 14807
telemt_me_reconnect_success_total 13969
telemt_me_reader_eof_total 14790
telemt_me_idle_close_by_peer_total 14788
telemt_me_route_drop_no_conn_total 235826
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479257
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2217
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 684
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14132
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13947
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 481494
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 4681174158 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 131800270652 (122.75 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 68929.3 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 986143
telemt_connections_bad_total 7502
telemt_handshake_timeouts_total 97340
telemt_upstream_connect_attempt_total 18650
telemt_upstream_connect_success_total 18423
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 18650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 26260
telemt_me_reconnect_success_total 13894
telemt_me_reader_eof_total 14930
telemt_me_idle_close_by_peer_total 14930
telemt_me_route_drop_no_conn_total 323246
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 842520
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2405
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1693
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 951
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14462
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13883
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 843409
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 9997684477 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 256503565165 (238.89 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 68929.8 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719115
telemt_connections_bad_total 64772
telemt_handshake_timeouts_total 69612
telemt_upstream_connect_attempt_total 18968
telemt_upstream_connect_success_total 18968
telemt_upstream_connect_attempts_per_request{bucket="1"} 18968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 712
telemt_me_reconnect_attempts_total 16580
telemt_me_reconnect_success_total 15526
telemt_me_reader_eof_total 16491
telemt_me_idle_close_by_peer_total 16490
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 224901
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1258
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 783
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 15710
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15503
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 562175
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 6560614012 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 159511186504 (148.56 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68929.3 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763186
telemt_connections_bad_total 5984
telemt_handshake_timeouts_total 7246
telemt_upstream_connect_attempt_total 18694
telemt_upstream_connect_success_total 18620
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 768
telemt_me_reconnect_attempts_total 18852
telemt_me_reconnect_success_total 15060
telemt_me_reader_eof_total 15919
telemt_me_idle_close_by_peer_total 15919
telemt_me_route_drop_no_conn_total 261696
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691519
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2953
telemt_desync_full_logged_total 1117
telemt_desync_suppressed_total 1836
telemt_desync_frames_bucket_total{bucket="1_2"} 1033
telemt_desync_frames_bucket_total{bucket="3_10"} 1209
telemt_desync_frames_bucket_total{bucket="gt_10"} 711
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15371
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15060
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 691203
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 10905124827 (10.16 GB)
telemt_user_octets_to_client{user="hello"} 248831161682 (231.74 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 123
```