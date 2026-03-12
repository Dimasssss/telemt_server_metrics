# Server Metrics 2026-03-12 11:41:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20564.4 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696977
telemt_connections_bad_total 1498
telemt_handshake_timeouts_total 3969
telemt_upstream_connect_attempt_total 3940
telemt_upstream_connect_success_total 3914
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 6754
telemt_me_reconnect_success_total 2862
telemt_me_reader_eof_total 3084
telemt_me_idle_close_by_peer_total 3084
telemt_me_route_drop_no_conn_total 244152
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3307
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 2466
telemt_desync_frames_bucket_total{bucket="1_2"} 853
telemt_desync_frames_bucket_total{bucket="3_10"} 1208
telemt_desync_frames_bucket_total{bucket="gt_10"} 1246
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3013
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2849
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 672044
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 11752795708 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 187386064820 (174.52 GB)
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50184.9 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363763
telemt_connections_bad_total 4344
telemt_handshake_timeouts_total 15384
telemt_upstream_connect_attempt_total 12343
telemt_upstream_connect_success_total 12337
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 822
telemt_me_reconnect_attempts_total 9707
telemt_me_reconnect_success_total 9652
telemt_me_reader_eof_total 10261
telemt_me_idle_close_by_peer_total 10261
telemt_me_route_drop_no_conn_total 103801
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323158
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 873
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 566
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9738
telemt_me_writer_restored_same_endpoint_total 9643
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 323626
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 4471152031 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 113547864578 (105.75 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 50184.9 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847476
telemt_connections_bad_total 4193
telemt_handshake_timeouts_total 62709
telemt_upstream_connect_attempt_total 12322
telemt_upstream_connect_success_total 12317
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 702
telemt_me_reconnect_attempts_total 9547
telemt_me_reconnect_success_total 9467
telemt_me_reader_eof_total 9960
telemt_me_idle_close_by_peer_total 9960
telemt_me_route_drop_no_conn_total 201445
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2575
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1815
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 894
telemt_desync_frames_bucket_total{bucket="gt_10"} 1348
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9489
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9426
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 565702
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 7597779756 (7.08 GB)
telemt_user_octets_to_client{user="hello"} 180590333077 (168.19 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 50185.2 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460672
telemt_connections_bad_total 3224
telemt_handshake_timeouts_total 43186
telemt_upstream_connect_attempt_total 13347
telemt_upstream_connect_success_total 13295
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 13347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1002
telemt_me_reconnect_attempts_total 10838
telemt_me_reconnect_success_total 10792
telemt_me_reader_eof_total 11446
telemt_me_idle_close_by_peer_total 11446
telemt_me_route_drop_no_conn_total 151833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 773
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10870
telemt_me_writer_restored_same_endpoint_total 10771
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 384404
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 4437864752 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 145489567092 (135.50 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50185.0 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520959
telemt_connections_bad_total 1669
telemt_handshake_timeouts_total 3991
telemt_upstream_connect_attempt_total 16369
telemt_upstream_connect_success_total 16178
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 16369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 782
telemt_me_reconnect_attempts_total 15675
telemt_me_reconnect_success_total 13669
telemt_me_reader_eof_total 14206
telemt_me_idle_close_by_peer_total 14206
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 171255
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487844
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2061
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1375
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 735
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13866
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 13643
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 487767
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 5585421052 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 119354424488 (111.16 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 115
```