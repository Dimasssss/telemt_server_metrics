# Server Metrics 2026-03-14 09:29:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 185427.0 (51h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5285880
telemt_connections_bad_total 50541
telemt_handshake_timeouts_total 118606
telemt_upstream_connect_attempt_total 38872
telemt_upstream_connect_success_total 38621
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 38872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 7504
telemt_me_reconnect_attempts_total 38301
telemt_me_reconnect_success_total 27086
telemt_me_reader_eof_total 29066
telemt_me_idle_close_by_peer_total 29065
telemt_me_route_drop_no_conn_total 1998310
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4842399
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18505
telemt_desync_full_logged_total 5058
telemt_desync_suppressed_total 13447
telemt_desync_frames_bucket_total{bucket="1_2"} 4566
telemt_desync_frames_bucket_total{bucket="3_10"} 7046
telemt_desync_frames_bucket_total{bucket="gt_10"} 6893
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 27834
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27073
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 748
telemt_user_connections_total{user="hello"} 4843877
telemt_user_connections_current{user="hello"} 1681
telemt_user_octets_from_client{user="hello"} 74274371300 (69.17 GB)
telemt_user_octets_to_client{user="hello"} 1547259034849 (1.41 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85091.1 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 948410
telemt_connections_bad_total 54651
telemt_handshake_timeouts_total 19188
telemt_upstream_connect_attempt_total 22544
telemt_upstream_connect_success_total 22256
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 2216
telemt_me_reconnect_attempts_total 25861
telemt_me_reconnect_success_total 15990
telemt_me_reader_eof_total 17148
telemt_me_idle_close_by_peer_total 17147
telemt_me_route_drop_no_conn_total 316651
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772003
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2182
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1495
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16527
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 15982
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 773900
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 8219883741 (7.66 GB)
telemt_user_octets_to_client{user="hello"} 267609987904 (249.23 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 215047.5 (59h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3764800
telemt_connections_bad_total 44528
telemt_handshake_timeouts_total 248590
telemt_upstream_connect_attempt_total 48526
telemt_upstream_connect_success_total 48505
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10880
telemt_me_reconnect_attempts_total 42499
telemt_me_reconnect_success_total 37506
telemt_me_reader_eof_total 39821
telemt_me_idle_close_by_peer_total 39820
telemt_me_route_drop_no_conn_total 1293063
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3144269
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10166
telemt_desync_full_logged_total 3452
telemt_desync_suppressed_total 6714
telemt_desync_frames_bucket_total{bucket="1_2"} 1815
telemt_desync_frames_bucket_total{bucket="3_10"} 3689
telemt_desync_frames_bucket_total{bucket="gt_10"} 4662
telemt_pool_swap_total 201
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38028
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37465
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 3143441
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 53254061560 (49.60 GB)
telemt_user_octets_to_client{user="hello"} 1125844602009 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 215050.1 (59h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2489579
telemt_connections_bad_total 23371
telemt_handshake_timeouts_total 308461
telemt_upstream_connect_attempt_total 66604
telemt_upstream_connect_success_total 64106
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 66330
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20623
telemt_me_reconnect_attempts_total 58048
telemt_me_reconnect_success_total 46400
telemt_me_reader_eof_total 49745
telemt_me_idle_close_by_peer_total 49738
telemt_me_route_drop_no_conn_total 833452
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1954152
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4021
telemt_desync_full_logged_total 1314
telemt_desync_suppressed_total 2707
telemt_desync_frames_bucket_total{bucket="1_2"} 1130
telemt_desync_frames_bucket_total{bucket="3_10"} 1644
telemt_desync_frames_bucket_total{bucket="gt_10"} 1247
telemt_pool_swap_total 187
telemt_me_writer_removed_unexpected_total 47161
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46376
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1960319
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 29355302975 (27.34 GB)
telemt_user_octets_to_client{user="hello"} 709193805534 (660.49 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84483.6 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 932649
telemt_connections_bad_total 13460
telemt_handshake_timeouts_total 12214
telemt_upstream_connect_attempt_total 21414
telemt_upstream_connect_success_total 20844
telemt_upstream_connect_fail_total 570
telemt_upstream_connect_attempts_per_request{bucket="1"} 21414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 570
telemt_me_keepalive_timeout_total 1679
telemt_me_reconnect_attempts_total 68048
telemt_me_reconnect_success_total 16645
telemt_me_reader_eof_total 18660
telemt_me_idle_close_by_peer_total 18659
telemt_me_route_drop_no_conn_total 357295
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865866
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2292
telemt_desync_full_logged_total 714
telemt_desync_suppressed_total 1578
telemt_desync_frames_bucket_total{bucket="1_2"} 756
telemt_desync_frames_bucket_total{bucket="3_10"} 866
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18406
telemt_me_refill_failed_total 1601
telemt_me_writer_restored_same_endpoint_total 16640
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1761
telemt_user_connections_total{user="hello"} 865809
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 15478040416 (14.42 GB)
telemt_user_octets_to_client{user="hello"} 292664114276 (272.56 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 126
```