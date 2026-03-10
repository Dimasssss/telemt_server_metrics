# Server Metrics 2026-03-10 22:34:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29227.2 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737498
telemt_connections_bad_total 8928
telemt_handshake_timeouts_total 8349
telemt_upstream_connect_attempt_total 6297
telemt_upstream_connect_success_total 6288
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 16404
telemt_me_reconnect_success_total 4745
telemt_me_reader_eof_total 5235
telemt_me_idle_close_by_peer_total 5235
telemt_me_route_drop_no_conn_total 307302
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697391
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3459
telemt_desync_full_logged_total 966
telemt_desync_suppressed_total 2493
telemt_desync_frames_bucket_total{bucket="1_2"} 995
telemt_desync_frames_bucket_total{bucket="3_10"} 1296
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5147
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4739
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 697193
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 9996669660 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 211294492520 (196.78 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29283.9 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319791
telemt_connections_bad_total 2363
telemt_handshake_timeouts_total 17578
telemt_upstream_connect_attempt_total 12904
telemt_upstream_connect_success_total 10037
telemt_upstream_connect_fail_total 2867
telemt_upstream_connect_attempts_per_request{bucket="1"} 12904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2867
telemt_me_keepalive_timeout_total 1377
telemt_me_reconnect_attempts_total 6385
telemt_me_reconnect_success_total 5579
telemt_me_reader_eof_total 5848
telemt_me_idle_close_by_peer_total 5846
telemt_me_route_drop_no_conn_total 166928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269856
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1616
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 495
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5667
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5558
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 272129
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 2666809210 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 64140223936 (59.74 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 29283.8 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528447
telemt_connections_bad_total 3363
telemt_handshake_timeouts_total 33765
telemt_upstream_connect_attempt_total 8067
telemt_upstream_connect_success_total 7948
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 8067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 16419
telemt_me_reconnect_success_total 5364
telemt_me_reader_eof_total 5900
telemt_me_idle_close_by_peer_total 5900
telemt_me_route_drop_no_conn_total 183371
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462985
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1490
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5794
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5353
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 463917
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 6636461233 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 148312882561 (138.13 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 29284.3 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371601
telemt_connections_bad_total 28194
telemt_handshake_timeouts_total 33290
telemt_upstream_connect_attempt_total 8128
telemt_upstream_connect_success_total 8128
telemt_upstream_connect_attempts_per_request{bucket="1"} 8128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 7642
telemt_me_reconnect_success_total 6618
telemt_me_reader_eof_total 6960
telemt_me_idle_close_by_peer_total 6960
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 118861
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297229
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6720
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6604
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 296904
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 4047584328 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 87018721564 (81.04 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29283.9 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391874
telemt_connections_bad_total 2533
telemt_handshake_timeouts_total 2574
telemt_upstream_connect_attempt_total 9081
telemt_upstream_connect_success_total 9045
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 9081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 11261
telemt_me_reconnect_success_total 7502
telemt_me_reader_eof_total 7871
telemt_me_idle_close_by_peer_total 7871
telemt_me_route_drop_no_conn_total 137155
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365007
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2143
telemt_desync_full_logged_total 818
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 915
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7724
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7502
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 364831
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 6429389368 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 137568432232 (128.12 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 44
```